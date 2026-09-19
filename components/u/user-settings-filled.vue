<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg-_9kbpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xg-_9kbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:user-settings-filled" /></template>
