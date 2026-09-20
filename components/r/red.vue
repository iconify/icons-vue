<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk9_68w6u.css';
import '../../css/b/bm337jbbl.css';
import '../../css/f/ff8xd2bsy.css';
import '../../css/f/f8vhwlbyu.css';
import '../../css/r/rt6j9wblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":200,"height":200};
const content = `<path class="yk9_68w6u"/><path class="bm337jbbl"/><path class="ff8xd2bsy"/><path class="f8vhwlbyu"/><path class="rt6j9wblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:red" /></template>
