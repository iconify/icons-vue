<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b07gwsbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":458,"height":512};
const content = `<path class="b07gwsbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:terraform" /></template>
