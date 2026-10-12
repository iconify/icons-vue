<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yenqbtb5g.css';
import '../../css/e/e_r9uibzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yenqbtb5g"/><path class="e_r9uibzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-round-check-filled" /></template>
