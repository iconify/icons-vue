<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5npjt0gk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5npjt0gk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-filled" /></template>
