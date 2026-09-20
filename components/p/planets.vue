<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/riomwtb3m.css';
import '../../css/x/xcwrauxib.css';
import '../../css/l/ltwci7nut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="riomwtb3m"/><path class="xcwrauxib"/><path class="ltwci7nut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:planets" /></template>
