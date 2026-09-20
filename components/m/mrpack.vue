<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx-_ic5tj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":514,"height":514};
const content = `<path class="sx-_ic5tj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:mrpack" /></template>
