<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvnvmob9i.css';
import '../../css/u/u769r-biz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvnvmob9i"/><path clip-rule="evenodd" class="u769r-biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mouse-off-filled" /></template>
