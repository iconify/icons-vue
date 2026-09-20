<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fva8p8ufs.css';
import '../../css/u/u9tojb6xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fva8p8ufs"/><path class="u9tojb6xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:mail-send-reply-all-solid" /></template>
