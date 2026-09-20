<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygz7wxvlo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygz7wxvlo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:mixpanel" /></template>
