<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mytq8j2nt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mytq8j2nt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:mouse-pointer-fill" /></template>
