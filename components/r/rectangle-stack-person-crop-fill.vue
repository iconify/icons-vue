<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlkw4ackd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="hlkw4ackd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:rectangle-stack-person-crop-fill" /></template>
