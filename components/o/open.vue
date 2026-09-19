<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9q94dj6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":11};
const content = `<path class="s9q94dj6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:open" /></template>
