<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaa1sl7cd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uaa1sl7cd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mailbox-solid" /></template>
