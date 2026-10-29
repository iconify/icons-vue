<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/ioij23bbf.css';
import '../../css/c/c2-aoy6rw.css';
import '../../css/r/rbkip6b3f.css';
import '../../css/v/v7vmxhb7b.css';
import '../../css/j/j7hpscfgt.css';
import '../../css/i/i8enl9bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ioij23bbf wm-k"/><path class="c2-aoy6rw wm-a"/><path class="rbkip6b3f wm-shadow"/><path class="v7vmxhb7b wm-k"/><path class="j7hpscfgt wm-a"/><path class="i8enl9bjs wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mic-vocal-engrave" /></template>
