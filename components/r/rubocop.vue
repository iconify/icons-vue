<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr4rpnb-k.css';
import '../../css/a/a698f-07m.css';
import '../../css/y/y_7o9gs7y.css';
import '../../css/i/irx0otbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gr4rpnb-k"/><path class="a698f-07m"/><path class="y_7o9gs7y"/><path class="irx0otbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:rubocop" /></template>
