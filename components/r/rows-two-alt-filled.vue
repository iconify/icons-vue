<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo1kesznu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xo1kesznu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:rows-two-alt-filled" /></template>
