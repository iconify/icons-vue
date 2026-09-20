<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4so3qlya.css';
import '../../css/l/lsxdb1s3e.css';
import '../../css/c/cyj7fswlr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p4so3qlya"/><path class="lsxdb1s3e"/><circle class="cyj7fswlr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:user-pages-ltr" /></template>
