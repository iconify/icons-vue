<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szo7gubys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szo7gubys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:moon-alt-fill" /></template>
