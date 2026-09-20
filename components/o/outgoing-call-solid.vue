<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lncb9db9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lncb9db9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:outgoing-call-solid" /></template>
