<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae8echs6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ae8echs6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:mint" /></template>
