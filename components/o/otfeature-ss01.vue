<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8aoz-b-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="b8aoz-b-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:otfeature-ss01" /></template>
