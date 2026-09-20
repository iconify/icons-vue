<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs314zbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs314zbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:webgl" /></template>
