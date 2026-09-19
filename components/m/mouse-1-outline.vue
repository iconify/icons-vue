<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zx-8yob4q.css';
import '../../css/u/u86dwhbsn.css';
import '../../css/t/tnlmsebze.css';
import '../../css/z/z6ylehhen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="zx-8yob4q"/><path class="u86dwhbsn"/><path class="tnlmsebze"/><path class="z6ylehhen"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:mouse-1-outline" /></template>
