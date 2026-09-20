<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7e9t3b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7e9t3b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-circle-x" /></template>
