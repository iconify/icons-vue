<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlko4hp7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":580,"height":684};
const content = `<path class="hlko4hp7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:server" /></template>
