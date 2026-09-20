<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6y9m7b9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6y9m7b9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:soundcloud-logo-bold" /></template>
