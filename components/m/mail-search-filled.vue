<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edfoyo7yi.css';
import '../../css/c/c1uddcbcz.css';
import '../../css/z/zc_h-6bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="edfoyo7yi"/><path class="c1uddcbcz"/><path class="zc_h-6bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mail-search-filled" /></template>
