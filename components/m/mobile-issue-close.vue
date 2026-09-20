<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi2hptddu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pi2hptddu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:mobile-issue-close" /></template>
