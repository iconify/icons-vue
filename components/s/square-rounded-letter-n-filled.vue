<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb99kkbbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jb99kkbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-letter-n-filled" /></template>
