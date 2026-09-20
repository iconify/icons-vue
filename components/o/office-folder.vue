<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/q/ql59iqbnu.css';
import '../../css/x/x207j0b5s.css';
import '../../css/g/gdgyiqj9v.css';
import '../../css/q/qnwvedb8u.css';
import '../../css/p/p7wwu3o2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ql59iqbnu"/><path class="x207j0b5s"/><path class="gdgyiqj9v"/><path class="qnwvedb8u"/><path class="p7wwu3o2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:office-folder" /></template>
