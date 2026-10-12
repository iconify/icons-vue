<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s24s3go5f.css';
import '../../css/a/aba_xubdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s24s3go5f"/><path class="aba_xubdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:monitor-dot-filled" /></template>
