<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adqrupgrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tv-remote-outline" /></template>
<style>
.adqrupgrx {
  fill: currentColor;
  d: path("M9.616 21h4.769q.269 0 .442-.173t.173-.442v-5.789q-.529.648-1.31 1.026Q12.907 16 12 16t-1.69-.378q-.78-.378-1.31-1.026v5.789q0 .269.173.442t.443.173m4.509-6.875Q15 13.25 15 12t-.875-2.125T12 9t-2.125.875T9 12t.875 2.125T12 15t2.125-.875M9 9.404q.529-.648 1.31-1.026Q11.093 8 12 8t1.69.378q.781.378 1.31 1.026V3.616q0-.27-.173-.443T14.385 3h-4.77q-.269 0-.442.173T9 3.616zM9.616 22q-.691 0-1.153-.462T8 20.385V3.615q0-.69.463-1.152T9.616 2h4.769q.69 0 1.153.463T16 3.616v16.769q0 .69-.462 1.153T14.385 22zm1.495-9.11q-.361-.361-.361-.89t.36-.89q.361-.36.89-.36t.89.36q.36.361.36.89t-.36.89q-.361.36-.89.36t-.89-.36m1.41-7.37q.21-.21.21-.52t-.21-.52t-.52-.21t-.52.21t-.21.52t.21.52t.52.21t.52-.21M12 8");
}

</style>
