<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b51e4wr8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b51e4wr8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:notification-new-filled" /></template>
