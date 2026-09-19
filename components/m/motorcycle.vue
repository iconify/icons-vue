<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vdxtknbrp.css';
import '../../css/o/o6hkjob2p.css';
import '../../css/x/xha9vk2rs.css';
import '../../css/b/bepj-i6iu.css';
import '../../css/t/twux5nbod.css';
import '../../css/z/zmg998kja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="vdxtknbrp"/><path clip-rule="evenodd" class="o6hkjob2p"/><path class="xha9vk2rs"/><path clip-rule="evenodd" class="bepj-i6iu"/><path class="twux5nbod"/><path class="zmg998kja"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:motorcycle" /></template>
