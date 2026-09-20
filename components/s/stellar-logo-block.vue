<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bszvb5wjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bszvb5wjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:stellar-logo-block" /></template>
