<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbncc194d.css';
import '../../css/r/rnfj33zxy.css';
import '../../css/x/xpiiaw94l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<g clip-rule="evenodd" class="xbncc194d"><path class="rnfj33zxy"/><path class="xpiiaw94l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:pin-outline" /></template>
