<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrectqbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="mrectqbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:rectangle-list" /></template>
