<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbt3qw.css';
import '../../css/c/c_rqdr.css';
import '../../css/y/ydovum.css';
import '../../css/x/xhxeiv.css';
import '../../css/s/so-from-56.css';
import '../../css/f/fade-to-1.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbt3qw"/><path class="c_rqdr ydovum"/><path class="xhxeiv ydovum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:moon" /></template>
