<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtefmjolt.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/j/jzfxvzblz.css';
import '../../css/g/gz0i5bqap.css';
import '../../css/o/o-zxexbtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="jtefmjolt"/><g class="jn8qy4bru"><path class="jzfxvzblz"/><path class="gz0i5bqap"/><path class="o-zxexbtq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:thong-sandal" /></template>
