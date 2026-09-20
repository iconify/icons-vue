<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa7jysbjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aa7jysbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:znn" /></template>
