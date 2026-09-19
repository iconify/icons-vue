<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0rcu6byt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="w0rcu6byt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:thermometer-sun" /></template>
