<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgwxuac0h.css';
import '../../css/b/bbzbypbsp.css';
import '../../css/w/wpc3x9bjb.css';
import '../../css/z/zx_78cd7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cgwxuac0h"/><path class="bbzbypbsp"/><path class="wpc3x9bjb"/><path class="zx_78cd7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconito:oregano" /></template>
