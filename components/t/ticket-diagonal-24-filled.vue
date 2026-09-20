<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej6kacy4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ticket-diagonal-24-filled" /></template>
<style>
.ej6kacy4y {
  fill: currentColor;
  d: path("M12.619 2.499a2.25 2.25 0 0 1 3.01.154l.993.992c.439.44.346 1.093-.015 1.45a1.626 1.626 0 1 0 2.296 2.297l.07-.064c.343-.286.889-.355 1.295-.028l.085.077l.984.984l.155.17a2.25 2.25 0 0 1 0 2.84l-.155.172l-2.367 2.366l-1.203-1.203a.75.75 0 0 0-1.06 1.06l1.203 1.203l-6.365 6.367a2.25 2.25 0 0 1-3.011.154l-.171-.154l-.984-.985c-.44-.44-.346-1.093.014-1.45l.107-.116a1.6 1.6 0 0 0 .375-1.035a1.626 1.626 0 0 0-2.778-1.144c-.357.36-1.01.452-1.45.014l-.992-.992a2.25 2.25 0 0 1 0-3.182L9.02 6.08l1.212 1.212a.75.75 0 0 0 1.06-1.06l-1.211-1.213l2.367-2.366zm1.148 6.207a.75.75 0 0 0-1.06 1.06l1.525 1.526a.75.75 0 0 0 1.06-1.06z");
}

</style>
