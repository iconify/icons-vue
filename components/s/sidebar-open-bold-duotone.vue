<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1nbikbny.css';
import '../../css/h/hd3mzwb_t.css';
import '../../css/y/ydzn23buh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g1nbikbny"/><path class="hd3mzwb_t"/><path class="ydzn23buh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sidebar-open-bold-duotone" /></template>
