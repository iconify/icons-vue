<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfmg-5_6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wfmg-5_6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:person" /></template>
