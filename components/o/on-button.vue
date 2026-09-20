<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0flwka0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0flwka0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:on-button" /></template>
