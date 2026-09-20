<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lsd67ebtj.css';
import '../../css/o/o1uhj0kov.css';
import '../../css/b/bud1ugbge.css';
import '../../css/c/c6rhvn7kc.css';
import '../../css/g/gaw0ybcky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lsd67ebtj"/><path class="o1uhj0kov"/><path class="bud1ugbge"/><path class="c6rhvn7kc"/><path clip-rule="evenodd" class="gaw0ybcky"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:phone-rotate-duotone" /></template>
