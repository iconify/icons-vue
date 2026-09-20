<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xyjtgccot.css';
import '../../css/b/b1erracoq.css';
import '../../css/g/gd2iygb3r.css';
import '../../css/f/fb7uf6bfd.css';
import '../../css/u/u70iueb1k.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g class="xyjtgccot"><path class="b1erracoq"/><path clip-rule="evenodd" class="gd2iygb3r"/></g><path clip-rule="evenodd" class="fb7uf6bfd"/><path clip-rule="evenodd" class="u70iueb1k"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:tablet-off" /></template>
