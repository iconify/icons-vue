<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oir8vpbxa.css';
import '../../css/c/cpcvcqb5t.css';
import '../../css/w/w-o1zsb7d.css';
import '../../css/i/io9dsz-xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oir8vpbxa wm-a"/><path class="cpcvcqb5t wm-a"/><path class="w-o1zsb7d wm-k"/><path class="io9dsz-xx wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:medal" /></template>
