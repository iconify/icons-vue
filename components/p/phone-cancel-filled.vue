<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfzpukz8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wfzpukz8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:phone-cancel-filled" /></template>
