<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d2kvgvbvc.css';
import '../../css/t/thfq4gbnm.css';
import '../../css/w/wd4pbac6a.css';
import '../../css/k/kubn6vbik.css';
import '../../css/y/ywpiuebfh.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g clip-rule="evenodd" class="d2kvgvbvc"><path class="thfq4gbnm"/><path class="wd4pbac6a"/><path class="kubn6vbik"/><path class="ywpiuebfh"/></g><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:sword-off" /></template>
