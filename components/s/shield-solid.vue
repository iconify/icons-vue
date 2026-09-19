<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9m7zgb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9m7zgb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:shield-solid" /></template>
