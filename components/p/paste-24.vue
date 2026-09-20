<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o75vn0b-t.css';
import '../../css/k/kbzcbrwur.css';
import '../../css/w/wukahqb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o75vn0b-t"/><path class="kbzcbrwur"/><path clip-rule="evenodd" class="wukahqb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:paste-24" /></template>
