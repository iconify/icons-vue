<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/undukhbqa.css';
import '../../css/m/m_xvzmb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="undukhbqa"/><path clip-rule="evenodd" class="m_xvzmb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:search-filled" /></template>
