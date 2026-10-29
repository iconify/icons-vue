<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/zabkgx3jw.css';
import '../../css/p/p-s04tbug.css';
import '../../css/s/sonegacxa.css';
import '../../css/b/b8fnn2y3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="zabkgx3jw"/><path class="p-s04tbug wm-a"/><path class="sonegacxa wm-k"/><path class="b8fnn2y3r wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:square-code-sketch" /></template>
