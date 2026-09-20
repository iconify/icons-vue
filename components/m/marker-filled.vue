<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt8r-f.css';
import '../../css/s/s1ui7u.css';
import '../../css/f/fkzmsa.css';
import '../../css/s/so-from-46.css';
import '../../css/f/fade-to-1.css';
import '../../css/d/d-9jpx1r.css';
import '../../css/f/fill-to-1.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt8r-f s1ui7u"/><path class="fkzmsa s1ui7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:marker-filled" /></template>
