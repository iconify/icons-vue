<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu9i6vdsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="xu9i6vdsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:user-success-filled" /></template>
