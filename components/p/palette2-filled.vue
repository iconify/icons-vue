<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr7u70uhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gr7u70uhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:palette2-filled" /></template>
