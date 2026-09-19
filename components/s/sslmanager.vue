<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eim6lnoap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="eim6lnoap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:sslmanager" /></template>
