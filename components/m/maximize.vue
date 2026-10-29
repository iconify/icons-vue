<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/typ168lje.css';
import '../../css/b/brefaib6f.css';
import '../../css/g/gv1maybhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="typ168lje wm-shadow"/><path class="brefaib6f wm-k"/><path class="gv1maybhe wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:maximize" /></template>
