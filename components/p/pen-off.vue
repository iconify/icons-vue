<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a50pz2beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a50pz2beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pen-off" /></template>
