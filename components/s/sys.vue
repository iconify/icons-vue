<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz1pwcbyv.css';
import '../../css/n/nyd7drbdm.css';
import '../../css/d/dyces3hqx.css';
import '../../css/q/qfaikbcyt.css';
import '../../css/a/aka35hb7t.css';
import '../../css/a/a21e8f75v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bz1pwcbyv"/><path class="nyd7drbdm"/><path class="dyces3hqx"/><path class="qfaikbcyt"/><path class="aka35hb7t"/><path class="a21e8f75v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:sys" /></template>
