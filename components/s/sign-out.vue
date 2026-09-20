<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynf4fk1jh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":17};
const content = `<path class="ynf4fk1jh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:sign-out" /></template>
