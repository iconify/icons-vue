<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpk_r1xfw.css';
import '../../css/j/jwxrimbri.css';
import '../../css/r/rsw0cp66o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xpk_r1xfw"/><path class="jwxrimbri"/><path class="rsw0cp66o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:processing" /></template>
