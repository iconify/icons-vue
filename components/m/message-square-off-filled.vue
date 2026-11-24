<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7ukzsz6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7ukzsz6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-square-off-filled" /></template>
