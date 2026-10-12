<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx6xpabsn.css';
import '../../css/a/aovmzshjn.css';
import '../../css/a/ab5r28h8z.css';
import '../../css/y/yw8l68yim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qx6xpabsn"/><path class="aovmzshjn"/><path class="ab5r28h8z"/><path class="yw8l68yim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:person-list-stroke-20" /></template>
