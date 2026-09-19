<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3gfemb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3gfemb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-circle-code-filled" /></template>
