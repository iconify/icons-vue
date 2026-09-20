<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jw6sdmbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:swipe-vertical-outline" /></template>
<style>
.jw6sdmbpq {
  fill: currentColor;
  d: path("M3 21v-.865h2.314q-1.475-1.724-2.356-3.783t-.881-4.333q0-2.292.88-4.342t2.357-3.793H3V3h4.096v4.116h-.865V4.177q-1.47 1.67-2.379 3.646q-.91 1.977-.91 4.196q0 2.2.91 4.167q.91 1.968 2.379 3.618v-2.9h.865V21zm13.296-1.194q-.46.161-.96.149t-.955-.23l-6.32-2.934l.297-.597q.154-.269.402-.428t.548-.189l2.854-.317l-2.858-7.81q-.073-.208.015-.387t.296-.253t.388.015t.253.296l3.296 9.06l-3.75.328l5.006 2.314q.251.114.557.136t.577-.086l3.444-1.252q.987-.352 1.423-1.287q.437-.936.085-1.923l-1.375-3.75q-.073-.207.006-.387t.287-.253t.387.006t.253.287l1.375 3.75q.517 1.382-.093 2.687q-.611 1.305-1.994 1.803zm-1.769-6.26l-1.37-3.775q-.072-.208.016-.387q.089-.18.296-.253t.388.015t.253.296l1.375 3.75zm2.671-.986l-1.025-2.826q-.073-.207.016-.377t.296-.243t.387.005t.253.287l1.025 2.819zm-.107 2.7");
}

</style>
