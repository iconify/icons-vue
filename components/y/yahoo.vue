<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akdnkpb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":940,"height":614};
const content = `<path class="akdnkpb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:yahoo" /></template>
