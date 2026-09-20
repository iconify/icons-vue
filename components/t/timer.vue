<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfn7lsbck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfn7lsbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:timer" /></template>
