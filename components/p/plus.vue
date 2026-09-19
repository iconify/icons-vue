<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2ri24b9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i2ri24b9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:plus" /></template>
