<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwro-z_xc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwro-z_xc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:reddit" /></template>
