<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9sbsvbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":24};
const content = `<path class="s9sbsvbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:night-alt-snow" /></template>
