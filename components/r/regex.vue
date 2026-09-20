<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnyn3qbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnyn3qbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:regex" /></template>
