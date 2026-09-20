<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fos-ok0ha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fos-ok0ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sailfish-os" /></template>
