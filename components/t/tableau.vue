<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxmt3hbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxmt3hbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:tableau" /></template>
