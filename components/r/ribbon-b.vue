<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxxj4et5j.css';
import '../../css/g/gn_ky95ky.css';
import '../../css/b/bc6mt2bvs.css';
import '../../css/j/jwzr-db4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rxxj4et5j"/><path class="gn_ky95ky"/><g><path class="bc6mt2bvs"/><path class="jwzr-db4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ribbon-b" /></template>
