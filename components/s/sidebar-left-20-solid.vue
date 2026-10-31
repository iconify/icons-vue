<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an7mdmbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="an7mdmbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:sidebar-left-20-solid" /></template>
