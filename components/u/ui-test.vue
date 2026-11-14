<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2fl5xbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ui-test" /></template>
<style>
.x2fl5xbhk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 2.25H6.875q-2.123 0-3.624 1.501T1.75 7.375v6.25q0 2.123 1.501 3.624t3.624 1.501h6.706q-.037-.098-.071-.202l-.941-2.92q-.68-2.107.935-3.624q1.614-1.518 3.676-.707h.001l2.49.979q1.659.653 1.739 2.433q.079 1.781-1.514 2.579l-.846.422l-.345.806q1.136-.359 2.044-1.267q1.501-1.501 1.501-3.624v-6.25q0-2.123-1.501-3.624T17.125 2.25m-9.875 3h3.5q1.036 0 1.768.732t.732 1.768t-.732 1.768t-1.768.732h-3.5q-2.5 0-2.5-2.5t2.5-2.5m9.473 7.21l2.49.979q.905.356.948 1.326t-.825 1.406l-1.01.504q-.244.123-.352.375l-.535 1.246q-.397.933-1.413.886q-1.015-.047-1.325-1.015l-.942-2.922q-.437-1.355.601-2.331q1.038-.975 2.363-.454m-.548 1.396q-.442-.174-.788.152t-.2.777l.912 2.83l.495-1.155q.324-.757 1.062-1.127l1.002-.501z");
}

</style>
