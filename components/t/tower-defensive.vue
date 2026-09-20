<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwzwdmpba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iwzwdmpba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:tower-defensive" /></template>
