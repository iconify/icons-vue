<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlbcxttud.css';
import '../../css/b/b3qn-8h1z.css';
import '../../css/t/t_j61bbmi.css';
import '../../css/j/jded-0bwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dlbcxttud"/><path class="b3qn-8h1z"/><path class="t_j61bbmi"/><path class="jded-0bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:present" /></template>
