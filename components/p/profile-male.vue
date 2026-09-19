<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab5784bmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":32};
const content = `<path class="ab5784bmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:profile-male" /></template>
