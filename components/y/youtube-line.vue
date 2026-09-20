<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj_edtbco.css';
import '../../css/n/n3kf-o-ku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dj_edtbco"/><path class="n3kf-o-ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:youtube-line" /></template>
