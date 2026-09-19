<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5jx2rb3f.css';
import '../../css/y/y2e1v-8ak.css';
import '../../css/n/n9az18p2h.css';
import '../../css/e/edj7wwb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a5jx2rb3f"/><path class="y2e1v-8ak"/><path class="n9az18p2h"/><path class="edj7wwb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:rotate-to-portrait" /></template>
