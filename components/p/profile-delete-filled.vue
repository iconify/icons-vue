<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlh38yb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlh38yb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:profile-delete-filled" /></template>
