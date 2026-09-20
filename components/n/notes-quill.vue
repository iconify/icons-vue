<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/k/kyoivpb1v.css';
import '../../css/y/y84sanbev.css';
import '../../css/s/s_ax9mbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="kyoivpb1v"/><path class="y84sanbev"/><path class="s_ax9mbxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:notes-quill" /></template>
