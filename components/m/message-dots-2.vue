<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p56h_bbeb.css';
import '../../css/b/bhtd76b5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p56h_bbeb"/><path class="bhtd76b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-dots-2" /></template>
