<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omv9s7boz.css';
import '../../css/u/uekytfwoi.css';
import '../../css/c/cf023dkpi.css';
import '../../css/j/jzbgh9b7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="omv9s7boz"/><path class="uekytfwoi"/><path class="cf023dkpi"/><path class="jzbgh9b7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-emojis:melon-1" /></template>
