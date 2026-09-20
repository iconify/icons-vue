<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psp_wn.css';
import '../../css/y/ydovum.css';
import '../../css/d/ds-pxa.css';
import '../../css/c/cx-from-7px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psp_wn ydovum"/><circle class="ds-pxa ydovum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:switch-off-twotone-to-switch-twotone-transition" /></template>
