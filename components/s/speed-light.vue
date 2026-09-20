<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to-5kdesz.css';
import '../../css/e/ex0g_cb-o.css';
import '../../css/b/bcqf_8b-o.css';
import '../../css/s/scozvdbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><path class="ex0g_cb-o"/><path class="bcqf_8b-o"/><path class="scozvdbkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:speed-light" /></template>
