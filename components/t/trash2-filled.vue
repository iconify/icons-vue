<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwxfjwvnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwxfjwvnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:trash2-filled" /></template>
