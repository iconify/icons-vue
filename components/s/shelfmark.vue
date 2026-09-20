<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj8_-65to.css';
import '../../css/t/tig70s96w.css';
import '../../css/c/cf2gljolc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="xj8_-65to"/><path class="tig70s96w"/><path class="cf2gljolc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shelfmark" /></template>
