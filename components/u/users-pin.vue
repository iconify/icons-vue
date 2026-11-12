<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3m1z9bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3m1z9bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:users-pin" /></template>
