<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1f9k7btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":288,"height":512};
const content = `<path class="e1f9k7btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:mercury" /></template>
