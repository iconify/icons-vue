<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/e/en_xgrb1u.css';
import '../../css/f/fns7ilq0e.css';
import '../../css/v/vabrm_bjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="en_xgrb1u"/><path class="fns7ilq0e"/><path class="vabrm_bjl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:mg" /></template>
