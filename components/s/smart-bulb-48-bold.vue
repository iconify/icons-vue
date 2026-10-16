<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0m3wcb9a.css';
import '../../css/e/e72pk-7vm.css';
import '../../css/b/bowjjxblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u0m3wcb9a"/><path class="e72pk-7vm"/><path class="bowjjxblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-bulb-48-bold" /></template>
