<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb6dcj6zj.css';
import '../../css/b/b6j6qhhkx.css';
import '../../css/a/at-jsyr9c.css';
import '../../css/b/brb45-bry.css';
import '../../css/s/s3qm55vhm.css';
import '../../css/v/v7dbonx0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eb6dcj6zj"/><path class="b6j6qhhkx"/><path class="at-jsyr9c"/><path class="brb45-bry"/><path class="s3qm55vhm"/><path class="v7dbonx0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-easel" /></template>
