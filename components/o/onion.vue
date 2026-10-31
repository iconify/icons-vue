<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy3r-4b1v.css';
import '../../css/b/bjtu_p5xz.css';
import '../../css/v/vv7g44h6d.css';
import '../../css/e/e_x-e_2ba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qy3r-4b1v"/><path class="bjtu_p5xz"/><path class="vv7g44h6d"/><path class="e_x-e_2ba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconito:onion" /></template>
