<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjssmy8ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:news-channel" /></template>
<style>
.jjssmy8ke {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 6.278L9.092 2.54q-.045-.059-.101-.107t-.12-.085t-.135-.06q-.07-.023-.143-.032t-.147-.004t-.145.025t-.137.053t-.124.078q-.118.092-.192.221q-.074.13-.092.278t.021.292t.131.261l2.559 3.29H6q-1.76 0-3.005 1.245T1.75 11v6.5q0 1.76 1.245 3.005T6 21.75h12q1.76 0 3.005-1.245T22.25 17.5V11q0-1.76-1.245-3.005T18 6.75h-4.467l2.559-3.29q.045-.058.078-.124q.034-.066.053-.137q.02-.071.025-.145t-.004-.147t-.032-.143q-.024-.071-.06-.135q-.037-.064-.085-.12t-.107-.101t-.124-.078t-.137-.053t-.145-.025t-.147.004t-.143.032q-.071.024-.135.06q-.064.037-.12.085t-.101.107zm1.04 5.509l.885.618q.96.672.96 1.844t-.96 1.843l-.885.62q-1.118.782-2.329.152T9.5 14.869v-1.238q0-1.365 1.211-1.996q1.21-.63 2.329.152");
}

</style>
