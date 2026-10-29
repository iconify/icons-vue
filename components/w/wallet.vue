<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/as3krbbzb.css';
import '../../css/a/ax-9akbyt.css';
import '../../css/k/kbxro98gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="as3krbbzb"/><path class="ax-9akbyt"/><path class="kbxro98gm wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wallet" /></template>
