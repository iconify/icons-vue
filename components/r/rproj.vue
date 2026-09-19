<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anm5-5b-v.css';
import '../../css/v/vf3f05_0e.css';
import '../../css/q/qldxu1nsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path transform="matrix(1.26652 0 0 1.26466 -1.313 -1.572)" class="anm5-5b-v"/><circle class="vf3f05_0e"/><path class="qldxu1nsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:rproj" /></template>
