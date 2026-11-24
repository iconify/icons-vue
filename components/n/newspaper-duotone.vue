<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gbb67jbqy.css';
import '../../css/q/qdu8wjber.css';
import '../../css/b/b6lm5ubhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gbb67jbqy"/><path class="qdu8wjber"/><path clip-rule="evenodd" class="b6lm5ubhi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:newspaper-duotone" /></template>
