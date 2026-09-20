<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mh26g7bii.css';
import '../../css/w/wsqxpmcli.css';
import '../../css/g/gri55clhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mh26g7bii"/><path clip-rule="evenodd" class="wsqxpmcli"/><path class="gri55clhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-speak" /></template>
