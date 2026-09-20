<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-phgeb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-phgeb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:wireguard" /></template>
