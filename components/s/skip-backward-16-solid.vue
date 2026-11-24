<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbzn6k3gn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hbzn6k3gn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:skip-backward-16-solid" /></template>
