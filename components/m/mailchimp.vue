<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur7cbwjjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ur7cbwjjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:mailchimp" /></template>
