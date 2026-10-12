<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pihw0xj_y.css';
import '../../css/v/v28la4rjs.css';
import '../../css/b/b1yeqac8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pihw0xj_y"/><path class="v28la4rjs"/><path class="b1yeqac8a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:speaker-duotone" /></template>
