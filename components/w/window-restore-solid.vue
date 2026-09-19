<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/b_uee9b6t.css';
import '../../css/z/zs4v5jbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="b_uee9b6t"/><path class="zs4v5jbop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:window-restore-solid" /></template>
