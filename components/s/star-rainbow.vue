<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chprfjb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="chprfjb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:star-rainbow" /></template>
