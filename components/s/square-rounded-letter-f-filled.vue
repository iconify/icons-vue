<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdfa5hbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdfa5hbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-letter-f-filled" /></template>
